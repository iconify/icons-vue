<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyp6htmmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kyp6htmmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:red-square" /></template>
