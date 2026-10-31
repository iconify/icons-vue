<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8s2n6y0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8s2n6y0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:qr-code-round" /></template>
