<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exu6rknxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exu6rknxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:settings-fill-round" /></template>
