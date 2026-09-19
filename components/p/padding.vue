<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cms3obcuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="cms3obcuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:padding" /></template>
