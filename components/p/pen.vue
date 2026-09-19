<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgf8wccyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgf8wccyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:pen" /></template>
