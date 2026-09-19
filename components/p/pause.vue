<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agy0c8hur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agy0c8hur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:pause" /></template>
