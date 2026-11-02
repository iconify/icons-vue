<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7i9bg0qp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7i9bg0qp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-backward-30-line" /></template>
