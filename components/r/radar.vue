<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnp-8wb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bnp-8wb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:radar" /></template>
