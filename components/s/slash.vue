<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am3o8ac5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="am3o8ac5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="struq:slash" /></template>
