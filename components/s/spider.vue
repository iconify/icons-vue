<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5xl-o4hs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x5xl-o4hs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:spider" /></template>
