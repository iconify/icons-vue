<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zquszm3xo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zquszm3xo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:next-circle" /></template>
