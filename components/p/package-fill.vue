<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6x0jn-ig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6x0jn-ig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:package-fill" /></template>
