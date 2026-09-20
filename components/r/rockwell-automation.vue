<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt6_5ex8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vt6_5ex8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:rockwell-automation" /></template>
