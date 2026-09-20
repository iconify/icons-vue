<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qykhkv9au.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qykhkv9au"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:source-commit-end-local" /></template>
