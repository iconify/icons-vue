<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt6gjyb0z.css';
import '../../css/h/hs9yxrbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="tt6gjyb0z"/><path class="hs9yxrbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:stairway" /></template>
