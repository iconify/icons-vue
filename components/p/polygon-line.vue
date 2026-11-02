<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk7gl_bjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk7gl_bjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:polygon-line" /></template>
