<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf2tuqcuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pf2tuqcuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:spacing-small-16" /></template>
