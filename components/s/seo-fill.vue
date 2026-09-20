<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-o8ulbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-o8ulbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:seo-fill" /></template>
