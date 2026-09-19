<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8dec0bkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g8dec0bkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:new-moon" /></template>
