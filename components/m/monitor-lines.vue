<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khsak6icn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="khsak6icn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:monitor-lines" /></template>
