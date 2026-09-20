<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0rm_840l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0rm_840l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:sharp-corner" /></template>
