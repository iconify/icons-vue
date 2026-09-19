<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku0q42bjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ku0q42bjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:red-exclamation-mark" /></template>
