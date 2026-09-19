<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi36ombor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vi36ombor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shape-outline-filled" /></template>
