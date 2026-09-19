<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v35oqbc4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v35oqbc4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:womans-clothes" /></template>
