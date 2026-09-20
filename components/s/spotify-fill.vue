<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyc_qkbfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyc_qkbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:spotify-fill" /></template>
