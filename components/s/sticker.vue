<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9ixmxuxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9ixmxuxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sticker" /></template>
