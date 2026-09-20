<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6ibhaboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6ibhaboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:steering-wheel-line" /></template>
