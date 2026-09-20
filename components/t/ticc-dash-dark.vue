<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykan6rbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ykan6rbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ticc-dash-dark" /></template>
