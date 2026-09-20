<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k96xxzwek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k96xxzwek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:maze" /></template>
