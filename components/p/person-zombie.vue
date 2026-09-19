<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuo3ambkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iuo3ambkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:person-zombie" /></template>
