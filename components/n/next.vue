<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny8b-ebnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ny8b-ebnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:next" /></template>
