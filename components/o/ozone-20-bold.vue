<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p92x1lbfk.css';
import '../../css/x/x5bwyrbir.css';
import '../../css/x/xundq6axq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p92x1lbfk"/><path class="x5bwyrbir"/><path class="xundq6axq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ozone-20-bold" /></template>
