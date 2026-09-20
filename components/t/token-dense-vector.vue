<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccg9vfo6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ccg9vfo6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:token-dense-vector" /></template>
