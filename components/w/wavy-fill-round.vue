<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9b5wab0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9b5wab0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wavy-fill-round" /></template>
