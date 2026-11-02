<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx2h1bb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bx2h1bb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:paragraph-fill" /></template>
