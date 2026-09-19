<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru0o-1bas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="ru0o-1bas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:toggle-left" /></template>
