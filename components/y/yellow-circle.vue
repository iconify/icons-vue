<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iakis3b0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iakis3b0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:yellow-circle" /></template>
