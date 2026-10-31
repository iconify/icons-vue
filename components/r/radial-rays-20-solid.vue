<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4aqn1b6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="f4aqn1b6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:radial-rays-20-solid" /></template>
