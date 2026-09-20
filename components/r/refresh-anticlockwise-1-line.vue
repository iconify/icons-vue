<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aerx4bbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aerx4bbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:refresh-anticlockwise-1-line" /></template>
