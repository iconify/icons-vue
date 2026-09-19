<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8yrp8bih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":26};
const content = `<path class="j8yrp8bih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:wordmark-inbox-26" /></template>
