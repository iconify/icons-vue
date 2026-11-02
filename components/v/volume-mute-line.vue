<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3r9fnbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3r9fnbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:volume-mute-line" /></template>
