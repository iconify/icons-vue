<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy9whxbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy9whxbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:safari-line" /></template>
