<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="su0tyxbok"/><path class="f60fbrl_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-movie-filter" /></template>
<style>
.f60fbrl_p {
  fill: currentColor;
  d: path("m10 11l-.94 2.06L7 14l2.06.94L10 17l.94-2.06L13 14l-2.06-.94zm8.01-7l2 4h-3l-2-4h-2l2 4h-3l-2-4h-2l2 4h-3l-2-4h-1c-1.1 0-1.99.9-1.99 2l-.01 12c0 1.1.9 2 2 2h16c1.1 0 1.99-.9 1.99-2V4zm2 14h-16V6.47L5.77 10H16l-.63 1.37L14 12l1.37.63L16 14l.63-1.37L18 12l-1.37-.63L16 10h4.01z");
}

.su0tyxbok {
  fill: currentColor;
  d: path("M16.63 11.37L18 12l-1.37.63L16 14l-.63-1.37L14 12l1.37-.63L16 10H5.77L4.01 6.47V18h16v-8H16zm-5.69 3.57L10 17l-.94-2.06L7 14l2.06-.94L10 11l.94 2.06L13 14z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
