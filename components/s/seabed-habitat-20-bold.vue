<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv842m9yr.css';
import '../../css/u/um4pykb1b.css';
import '../../css/d/d8en99qry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yv842m9yr"/><path class="um4pykb1b"/><path class="d8en99qry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:seabed-habitat-20-bold" /></template>
