<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqseio53p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kqseio53p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:oncoming-fist" /></template>
