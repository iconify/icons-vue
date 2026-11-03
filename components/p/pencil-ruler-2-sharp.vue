<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2y7y2b7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pencil-ruler-2-sharp" /></template>
<style>
.g2y7y2b7w {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.6834 5.9833L16.5003 13.8001L22 16L19.8001 10.5003L11.9833 2.6834L11.2997 2L10.3333 2C9.7145 2 9.121 2.2458 8.6834 2.6834C8.2458 3.121 8 3.7145 8 4.3333L8 5.2997L8.6834 5.9833ZM12.8553 3.5555L9.5555 6.8553M7.2761 10.5108L4.1339 7.3686L2 5.235L2 22L18.765 22L16.6314 19.8661L12.9329 16.1676M12.9329 16.1676L7.2761 10.5108M7.2761 10.5108L4.9645 12.8223M12.9329 16.1676L10.6213 18.4792M10.1045 13.3392L7.7929 15.6508");
}

</style>
