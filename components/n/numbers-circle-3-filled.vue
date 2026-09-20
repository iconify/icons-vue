<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_22pptrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_22pptrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:numbers-circle-3-filled" /></template>
