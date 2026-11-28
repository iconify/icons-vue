<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0dys392l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0dys392l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pinterest-solid" /></template>
