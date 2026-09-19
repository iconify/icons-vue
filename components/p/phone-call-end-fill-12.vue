<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/joz7wcc-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="joz7wcc-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-call-end-fill-12" /></template>
