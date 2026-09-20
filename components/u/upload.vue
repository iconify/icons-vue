<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e--mljn9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e--mljn9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:upload" /></template>
