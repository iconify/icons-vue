<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueqilgogx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ueqilgogx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:recycle-fill" /></template>
