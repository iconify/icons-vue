<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7-ewwg-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u7-ewwg-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:nav-judgements" /></template>
