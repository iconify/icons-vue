<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1j879b-l.css';
import '../../css/p/pg468fg1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a1j879b-l"/><path class="pg468fg1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:rain-drizzle" /></template>
