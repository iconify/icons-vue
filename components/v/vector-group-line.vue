<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxl43mf-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxl43mf-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vector-group-line" /></template>
