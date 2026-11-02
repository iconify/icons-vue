<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmb7ilbst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmb7ilbst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tree-3-fill" /></template>
