<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg-i2sbad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cg-i2sbad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:signal-low" /></template>
