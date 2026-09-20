<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0u7fpb7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0u7fpb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:qlty" /></template>
