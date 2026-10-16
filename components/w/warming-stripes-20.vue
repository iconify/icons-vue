<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frrc-qxwg.css';
import '../../css/h/hce5i4bzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="frrc-qxwg"/><path class="hce5i4bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:warming-stripes-20" /></template>
