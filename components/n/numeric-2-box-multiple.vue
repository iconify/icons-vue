<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2db6qbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2db6qbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-2-box-multiple" /></template>
