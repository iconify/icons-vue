<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqop9mawr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nqop9mawr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:type-italic" /></template>
