<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubnupnbby.css';
import '../../css/z/zbrckdb1x.css';
import '../../css/m/mkvuid9tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ubnupnbby"/><path class="zbrckdb1x"/><path class="mkvuid9tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mine-shaft-20" /></template>
