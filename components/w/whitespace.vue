<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip7p42btd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ip7p42btd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:whitespace" /></template>
