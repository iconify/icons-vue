<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3rfekbkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="k3rfekbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:small-craft-advisory" /></template>
