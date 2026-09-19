<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-f7tacxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18,"height":24};
const content = `<path class="d-f7tacxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:tl" /></template>
