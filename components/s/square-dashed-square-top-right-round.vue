<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4jbj3f_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4jbj3f_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-top-right-round" /></template>
