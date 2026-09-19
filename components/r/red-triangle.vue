<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6-4pabmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r6-4pabmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:red-triangle" /></template>
