<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv39e_b2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gv39e_b2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:puzzle-outline" /></template>
