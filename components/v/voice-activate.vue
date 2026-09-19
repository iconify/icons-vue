<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr7ghh79r.css';
import '../../css/x/xu9naxyob.css';
import '../../css/j/j9p3709ef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nr7ghh79r"/><path class="xu9naxyob"/><path class="j9p3709ef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:voice-activate" /></template>
