<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrh7y0bpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="jrh7y0bpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:strikethrough-1" /></template>
