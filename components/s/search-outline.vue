<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-z3noepd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i-z3noepd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:search-outline" /></template>
