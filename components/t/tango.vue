<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p6ujfo41t"/><path class="igs37xb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tango" /></template>
<style>
.igs37xb_v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.793 15.91c2.748-.054 5.475-.305 8.138-.858a1.785 1.785 0 0 1 1.106 3.39c-3.82 1.28-7.731 1.968-11.683 2.331");
}

.p6ujfo41t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.495 21.159a328 328 0 0 1-4.434-.002c-3.39-.108-4.187-4.738-1.105-6.036a84 84 0 0 0 15.091-9.865c2.653-2.202 6.506.806 5.068 3.89c-2.902 6.34-6.247 11.847-8.581 18.138c-.804 2.421-1.73 4.958-1.125 7.007c.141.23.11.141.337.27c.097.057.417.154.498.156c4.28-.047 7.66-4.164 10.134-7.526c3.73-5.077 11.219.234 7.655 5.435h0c-3.2 4.346-7.092 8.184-12.511 10.08c-5.177 2.03-12.26.179-14.058-5.656c-1.868-6.483 2.197-14.452 6.323-21.45");
}

</style>
