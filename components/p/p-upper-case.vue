<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgjm2286q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":455,"height":735};
const content = `<path class="rgjm2286q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:p-upper-case" /></template>
