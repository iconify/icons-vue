<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rawbtr-6p.css';
import '../../css/p/p28r9n0-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="rawbtr-6p"/><path class="p28r9n0-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:shooting-star" /></template>
