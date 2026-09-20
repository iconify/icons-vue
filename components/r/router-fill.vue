<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cau7m0b9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cau7m0b9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:router-fill" /></template>
