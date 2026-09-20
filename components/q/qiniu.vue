<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmh8e6bux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmh8e6bux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:qiniu" /></template>
