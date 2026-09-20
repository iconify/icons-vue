<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvoo6thzj.css';
import '../../css/j/jz9026bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="jvoo6thzj"/><circle class="jz9026bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:musical-score" /></template>
