<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgh_0ybfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgh_0ybfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:new-folder-line" /></template>
