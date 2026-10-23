<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue6qx8t1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue6qx8t1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:wifi-low" /></template>
