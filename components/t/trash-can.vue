<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuua-_mlx.css';
import '../../css/w/w2u3wgntp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fuua-_mlx"/><path class="w2u3wgntp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:trash-can" /></template>
