<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz8zsd5cc.css';
import '../../css/w/wived3hxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wz8zsd5cc"/><path class="wived3hxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:move-horizontal-48-bold" /></template>
