<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he2h3cb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="he2h3cb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:selector-vertical-fill" /></template>
