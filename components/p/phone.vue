<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/seqji0d1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="seqji0d1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:phone" /></template>
