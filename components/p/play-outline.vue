<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz28_8bzx.css';
import '../../css/b/b93j9cbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gz28_8bzx"/><path class="b93j9cbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:play-outline" /></template>
