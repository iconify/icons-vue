<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/liyik2b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="liyik2b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:mnz" /></template>
