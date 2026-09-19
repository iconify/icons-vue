<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llwq-7b3r.css';
import '../../css/q/q585h1bqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="llwq-7b3r"/><path class="q585h1bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pause-past" /></template>
