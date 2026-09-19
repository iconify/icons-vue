<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3dpg2-tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="g3dpg2-tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:smiling-face-with-open-mouth-and-cold-sweat" /></template>
