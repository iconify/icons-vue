<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0hu8ieet.css';
import '../../css/e/e5_g43bxn.css';
import '../../css/u/u187tccwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="b0hu8ieet"/><path class="e5_g43bxn"/><path class="u187tccwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:pot-of-food" /></template>
