<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctgs7ibqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ctgs7ibqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:snake" /></template>
