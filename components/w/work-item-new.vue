<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5d9s8bzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j5d9s8bzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:work-item-new" /></template>
