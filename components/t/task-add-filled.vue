<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_hxwwbci.css';
import '../../css/d/dpnipcczy.css';
import '../../css/p/poiuuuhna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_hxwwbci"/><path class="dpnipcczy"/><path class="poiuuuhna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:task-add-filled" /></template>
