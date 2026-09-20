<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gewhw0bgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gewhw0bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:test-tube-line" /></template>
