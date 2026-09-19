<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3el5tocp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o3el5tocp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:speaker-x-mark-20-solid" /></template>
