<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/naif90b3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="naif90b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:stop-line" /></template>
