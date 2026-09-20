<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzsprsajn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzsprsajn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:nfc-line" /></template>
