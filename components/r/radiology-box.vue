<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpknzmbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpknzmbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:radiology-box" /></template>
