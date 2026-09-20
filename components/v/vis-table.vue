<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hidr92b8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hidr92b8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:vis-table" /></template>
