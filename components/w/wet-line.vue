<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc2aunb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qc2aunb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wet-line" /></template>
