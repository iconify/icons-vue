<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s29yto5-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s29yto5-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:no-one-under-eighteen" /></template>
