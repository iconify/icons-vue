<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9bwdn8yu.css';
import '../../css/u/u06779bpm.css';
import '../../css/c/cn03m5p3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="k9bwdn8yu"/><path class="u06779bpm"/><path class="cn03m5p3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:tooth" /></template>
