<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8oaf-6wj.css';
import '../../css/g/g34yiabzj.css';
import '../../css/f/fh7l44ama.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c8oaf-6wj"/><path class="g34yiabzj"/><path class="fh7l44ama"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:media-cast" /></template>
