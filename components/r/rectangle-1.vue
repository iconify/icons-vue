<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt9uchb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xt9uchb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:rectangle-1" /></template>
