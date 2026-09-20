<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8wox3mct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8wox3mct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-follow-2-line" /></template>
