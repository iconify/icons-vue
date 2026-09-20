<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9mzmqb3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c9mzmqb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:waze-dark" /></template>
