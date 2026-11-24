<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr2ifypni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr2ifypni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shovel-filled" /></template>
