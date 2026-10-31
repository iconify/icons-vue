<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx64cwy3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx64cwy3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:spell-check-fill-round" /></template>
