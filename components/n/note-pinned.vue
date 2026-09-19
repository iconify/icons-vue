<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqae2nbon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="hqae2nbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:note-pinned" /></template>
