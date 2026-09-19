<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jewu0nbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jewu0nbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:picture-stretch" /></template>
