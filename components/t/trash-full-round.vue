<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2h97cc7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2h97cc7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trash-full-round" /></template>
