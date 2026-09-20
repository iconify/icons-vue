<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cajk2g7zb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cajk2g7zb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:scissors-line" /></template>
