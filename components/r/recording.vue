<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b93j9cbjr.css';
import '../../css/m/mbcglytpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b93j9cbjr"/><path class="mbcglytpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:recording" /></template>
