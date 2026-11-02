<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5_b0h3gx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5_b0h3gx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sound-line-fill" /></template>
