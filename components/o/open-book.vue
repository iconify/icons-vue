<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-ff7xbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v-ff7xbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:open-book" /></template>
