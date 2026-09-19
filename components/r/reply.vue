<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jstkk1b5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jstkk1b5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:reply" /></template>
