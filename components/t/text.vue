<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9knb0b2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9knb0b2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:text" /></template>
