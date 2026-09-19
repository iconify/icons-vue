<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6g6chb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c6g6chb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:matrix" /></template>
