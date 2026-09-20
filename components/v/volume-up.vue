<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylykssbkx.css';
import '../../css/b/bwmi_1b-r.css';
import '../../css/p/p2v3_yp0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ylykssbkx"/><path class="bwmi_1b-r"/><path class="p2v3_yp0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:volume-up" /></template>
