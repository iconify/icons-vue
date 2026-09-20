<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usmo0gbrf.css';
import '../../css/t/tvepgg8ps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="usmo0gbrf"/><path class="tvepgg8ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:right-arrow" /></template>
