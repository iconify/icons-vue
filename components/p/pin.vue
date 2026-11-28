<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_cateq5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_cateq5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:pin" /></template>
