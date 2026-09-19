<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o547gvx6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o547gvx6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:projection-room" /></template>
