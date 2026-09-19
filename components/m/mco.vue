<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-1qv-lda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o-1qv-lda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:mco" /></template>
