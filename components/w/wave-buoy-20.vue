<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eji1th4ou.css';
import '../../css/w/wugtu-b6f.css';
import '../../css/t/td-qy1bhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eji1th4ou"/><path class="wugtu-b6f"/><path class="td-qy1bhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wave-buoy-20" /></template>
