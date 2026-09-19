<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlo5nub7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zlo5nub7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:triangle-solid-down-12" /></template>
