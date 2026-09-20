<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwiuv55ls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="iwiuv55ls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:nav-models" /></template>
