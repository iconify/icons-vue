<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spy95v0su.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spy95v0su"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:share-line" /></template>
