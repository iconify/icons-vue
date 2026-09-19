<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz3rsujwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="iz3rsujwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:preview" /></template>
