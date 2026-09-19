<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad1o_lclx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ad1o_lclx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:small-blue-diamond" /></template>
