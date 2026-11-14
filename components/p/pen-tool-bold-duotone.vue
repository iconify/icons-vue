<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtj83f9eb"/><path clip-rule="evenodd" class="uk1227l8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pen-tool-bold-duotone" /></template>
<style>
.qtj83f9eb {
  fill: currentColor;
  d: path("M16 6.5C17.2 8.2 18.5 9.60039 18.5 11.4004C18.4997 14.3208 15.4168 18.0728 12.75 21.1387V14C12.75 13.9512 12.7443 13.9036 12.7354 13.8574C13.4755 13.5642 14 12.8446 14 12C14 10.8954 13.1046 10 12 10C10.8954 10 10 10.8954 10 12C10 12.8442 10.524 13.5639 11.2637 13.8574C11.2548 13.9036 11.25 13.9512 11.25 14V21.1387C8.58323 18.0728 5.50027 14.3208 5.5 11.4004C5.5 9.60039 6.8 8.2 8 6.5H16Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.uk1227l8p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.5 4.7C16.5 5.5485 16.5 5.9728 16.2364 6.2364C15.9728 6.5 15.5485 6.5 14.7 6.5H9.3C8.4515 6.5 8.0272 6.5 7.7636 6.2364C7.5 5.9728 7.5 5.5485 7.5 4.7V3.8C7.5 2.9515 7.5 2.5272 7.7636 2.2636C8.0272 2 8.4515 2 9.3 2H14.7C15.5485 2 15.9728 2 16.2364 2.2636C16.5 2.5272 16.5 2.9515 16.5 3.8V4.7Z");
}

</style>
