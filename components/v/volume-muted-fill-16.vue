<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u70yb2bre.css';
import '../../css/i/i95u-8bjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u70yb2bre"/><path class="i95u-8bjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:volume-muted-fill-16" /></template>
