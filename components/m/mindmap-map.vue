<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlnfy5jfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wlnfy5jfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:mindmap-map" /></template>
