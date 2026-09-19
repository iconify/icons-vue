<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d57sztm3t.css';
import '../../css/z/z5b9-nbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d57sztm3t"/><path class="z5b9-nbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shape-exclude" /></template>
