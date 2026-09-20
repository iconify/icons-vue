<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfo0vldli.css';
import '../../css/o/o6jd39oeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="hfo0vldli"/><path class="o6jd39oeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:multiplication-sign" /></template>
