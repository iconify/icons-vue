<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-8vj6uno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shoppingmode-outline-rounded" /></template>
<style>
.b-8vj6uno {
  fill: currentColor;
  d: path("M11.15 22q-.375 0-.75-.15t-.675-.45l-7.15-7.15q-.3-.3-.437-.663T2 12.85t.138-.75t.437-.675l8.8-8.825q.275-.275.65-.438T12.8 2h7.175q.825 0 1.413.587T21.975 4v7.175q0 .4-.15.763t-.425.637L12.575 21.4q-.3.3-.675.45t-.75.15m0-2l8.825-8.85V4h-7.15L4 12.85zm6.325-12q.625 0 1.063-.437t.437-1.063t-.437-1.062T17.475 5t-1.062.438t-.438 1.062t.438 1.063T17.475 8M12 12");
}

</style>
