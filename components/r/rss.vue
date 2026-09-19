<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7ounnd_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":666,"height":680};
const content = `<path class="a7ounnd_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:rss" /></template>
