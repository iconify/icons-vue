<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q90zf6b5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q90zf6b5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:thumb-up-2-fill" /></template>
