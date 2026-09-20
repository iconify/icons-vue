<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgvo1z5ij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgvo1z5ij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:safe-alert-line" /></template>
