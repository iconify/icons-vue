<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq0a79eej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq0a79eej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:translate-2-line" /></template>
