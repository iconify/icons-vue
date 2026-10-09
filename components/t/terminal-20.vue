<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq_8t4b0z.css';
import '../../css/e/ef96-hbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jq_8t4b0z"/><path class="ef96-hbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:terminal-20" /></template>
