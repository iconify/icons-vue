<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exj8ttbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="exj8ttbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:skip-back-10" /></template>
