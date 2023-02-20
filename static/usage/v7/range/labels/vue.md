```html
<template>
  <ion-range label-placement="start">
    <div slot="label">Label at the Start</div>
  </ion-range>
  
  <br />
  
  <ion-range label-placement="end">
    <div slot="label">Label at the End</div>
  </ion-range>
  
  <br />
  
  <ion-range label-placement="fixed">
    <div slot="label">Fixed Width Label</div>
  </ion-range>
</template>

<script lang="ts">
  import { IonRange } from '@ionic/vue';
  import { defineComponent } from 'vue';

  export default defineComponent({
    components: { IonRange },
  });
</script>
```