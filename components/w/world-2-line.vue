<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz3fe2bww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rz3fe2bww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:world-2-line" /></template>
