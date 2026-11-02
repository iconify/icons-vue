<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo9yncb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oo9yncb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:scissors-line" /></template>
