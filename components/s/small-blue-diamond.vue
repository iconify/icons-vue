<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cggeh_puv.css';
import '../../css/l/lx9txg18g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="cggeh_puv"/><path class="lx9txg18g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:small-blue-diamond" /></template>
