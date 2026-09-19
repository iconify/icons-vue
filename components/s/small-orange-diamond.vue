<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0gu42b_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a0gu42b_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:small-orange-diamond" /></template>
