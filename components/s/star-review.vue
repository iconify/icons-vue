<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbv6tsbiz.css';
import '../../css/w/wtstr4z9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hbv6tsbiz"/><path class="wtstr4z9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:star-review" /></template>
