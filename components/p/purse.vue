<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w54qbjugd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w54qbjugd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:purse" /></template>
