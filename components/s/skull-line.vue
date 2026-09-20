<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5ogn4brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5ogn4brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:skull-line" /></template>
