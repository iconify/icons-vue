<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo5pkcblg.css';
import '../../css/k/k-4xfkbec.css';
import '../../css/l/lzmnrrp8b.css';
import '../../css/m/mxz5qbb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bo5pkcblg"/><path class="k-4xfkbec"/><path class="lzmnrrp8b"/><path class="mxz5qbb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:power-station-x-20" /></template>
