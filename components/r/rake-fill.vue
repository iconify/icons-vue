<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akjpw5bee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akjpw5bee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rake-fill" /></template>
