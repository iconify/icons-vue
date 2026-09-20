<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v64z8wbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tab-search-sharp" /></template>
<style>
.v64z8wbra {
  fill: currentColor;
  d: path("M2 20V4h20v8.05q-.375-.6-.888-1.137T20 9.975V6h-7v3.975q-1.35.875-2.175 2.338T10 15.5q0 1.325.488 2.475T11.825 20zm19.6 2l-2.7-2.7q-.55.325-1.15.513T16.5 20q-1.875 0-3.187-1.312T12 15.5t1.313-3.187T16.5 11t3.188 1.313T21 15.5q0 .65-.187 1.25T20.3 17.9l2.7 2.7zm-3.325-4.725Q19 16.55 19 15.5t-.725-1.775T16.5 13t-1.775.725T14 15.5t.725 1.775T16.5 18t1.775-.725");
}

</style>
