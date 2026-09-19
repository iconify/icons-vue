<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je0q_k_2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je0q_k_2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:video" /></template>
