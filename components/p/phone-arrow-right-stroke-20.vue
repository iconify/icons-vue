<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz11l89yb.css';
import '../../css/o/oimt4ji_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uz11l89yb"/><path class="oimt4ji_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-arrow-right-stroke-20" /></template>
