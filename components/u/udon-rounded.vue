<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdf5orxsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:udon-rounded" /></template>
<style>
.cdf5orxsj {
  fill: currentColor;
  d: path("M5.885 12h1.384V8.058H5.884zm0-4.827h1.384v-1.77l-1.384.158zM8.154 12h1.385V8.058H8.153zm0-4.827h1.385V5.161l-1.385.145zM3.43 14.769q-.145-.43-.235-.89t-.14-.935q-.05-.379.217-.661Q3.54 12 3.943 12H5V5.477q0-.298.215-.528q.214-.23.512-.28l14.775-1.607q.196-.031.347.095t.151.341q0 .16-.12.286t-.28.157L10.423 5.069v2.104h10.135q.19 0 .316.126t.126.317t-.126.316t-.316.126H10.423V12h9.633q.385 0 .652.283t.236.661q-.05.475-.14.935t-.235.89zM12 21q-2.742 0-4.914-1.449q-2.173-1.449-3.242-3.782h16.312q-1.07 2.333-3.241 3.782Q14.742 21 12 21");
}

</style>
