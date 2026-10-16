<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aat5akb2r.css';
import '../../css/x/xpyjtvwnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aat5akb2r"/><path class="xpyjtvwnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:voltage-high-20" /></template>
