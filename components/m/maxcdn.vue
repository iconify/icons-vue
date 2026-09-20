<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no7_fbapy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="no7_fbapy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:maxcdn" /></template>
