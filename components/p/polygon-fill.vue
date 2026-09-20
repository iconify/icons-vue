<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9q_8wb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9q_8wb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:polygon-fill" /></template>
