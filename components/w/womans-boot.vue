<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/joajan00w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="joajan00w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:womans-boot" /></template>
