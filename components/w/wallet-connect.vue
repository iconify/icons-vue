<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzy3-g9hz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wallet-connect" /></template>
<style>
.rzy3-g9hz {
  fill: var(--svg-color--3b99fc, #3b99fc);
  d: path("M6.685 8.71c2.935-2.813 7.695-2.813 10.63 0l.353.339a.35.35 0 0 1 0 .51l-1.208 1.158a.194.194 0 0 1-.266 0l-.486-.466c-2.048-1.963-5.368-1.963-7.416 0l-.52.498a.194.194 0 0 1-.266 0L6.297 9.592a.35.35 0 0 1 0-.51zm13.13 2.396l1.075 1.03a.35.35 0 0 1 0 .51l-4.85 4.648a.39.39 0 0 1-.531 0l-3.443-3.299a.097.097 0 0 0-.132 0l-3.442 3.3a.39.39 0 0 1-.532 0l-4.85-4.65a.35.35 0 0 1 0-.508l1.076-1.031a.387.387 0 0 1 .531 0l3.442 3.299a.097.097 0 0 0 .133 0l3.442-3.3a.387.387 0 0 1 .532 0l3.442 3.3a.097.097 0 0 0 .133 0l3.442-3.3a.39.39 0 0 1 .531 0");
}

</style>
