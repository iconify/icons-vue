<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wiuplsbzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wiuplsbzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:volcano" /></template>
