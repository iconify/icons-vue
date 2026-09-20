<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4nh9cb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4nh9cb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:search-eye-line" /></template>
