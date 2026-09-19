<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4291thww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="e4291thww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:pinned-fill" /></template>
