<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llwq-7b3r.css';
import '../../css/u/uufe-4b8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="llwq-7b3r"/><path class="uufe-4b8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pause-future" /></template>
