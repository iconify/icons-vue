<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q1fulp0_l"/><path class="vk9sievhj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-pen-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q1fulp0_l {
  d: path("M12.8419 3.02799C12.5643 3.00939 12.2835 2.99999 12 2.99999C6.4772 2.99999 2 6.58169 2 11C2 12.9769 2.915 14.8839 4.5686 16.353L5 21L9.5808 18.7624C10.3721 18.9202 11.1845 19 12 19C17.5228 19 22 15.4183 22 11C22 10.7234 21.9825 10.4501 21.9482 10.1807");
}

.vk9sievhj {
  fill: currentColor;
  d: path("M18.2632 9.6258L15.3319 12.5572C15.2361 12.653 15.1219 12.7283 14.9962 12.7786L10.8714 14.4285C10.7533 14.4757 10.6272 14.5 10.5 14.5C9.9477 14.5 9.5 14.0523 9.5 13.5C9.5 13.3728 9.5243 13.2467 9.5715 13.1286L11.2214 9.0038C11.2717 8.8781 11.347 8.7639 11.4428 8.6681L17.3054 2.8055C18.3794 1.7314 20.1206 1.7314 21.1945 2.8054C22.2685 3.8794 22.2685 5.6206 21.1945 6.6945Z");
  stroke: none;
}

</style>
