<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="esxisibaw"/><path class="ud65eiioe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:medal-ribbon-bold-duotone" /></template>
<style>
.esxisibaw {
  cx: 12px;
  cy: 9px;
  r: 7px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ud65eiioe {
  fill: currentColor;
  d: path("M7.54572 14.4002L7.35111 15L6.71424 17.323C6.0859 19.6148 5.77173 20.7608 6.19097 21.3881C6.3379 21.6079 6.535 21.7844 6.76372 21.9009C7.41634 22.2332 8.424 21.7081 10.4393 20.658C11.1099 20.3086 11.4452 20.1339 11.8014 20.0959C11.9335 20.0818 12.0665 20.0818 12.1986 20.0959C12.5548 20.1339 12.8901 20.3086 13.5607 20.658C15.576 21.7081 16.5837 22.2332 17.2363 21.9009C17.465 21.7844 17.6621 21.6079 17.809 21.3881C18.2283 20.7608 17.9141 19.6148 17.2858 17.323L16.6489 15L16.4543 14.4002C15.244 15.3996 13.6921 16 12 16C10.3079 16 8.75597 15.3996 7.54572 14.4002Z");
}

</style>
