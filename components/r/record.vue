<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p57ynbb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p57ynbb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:record" /></template>
