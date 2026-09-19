<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq_mpnbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fq_mpnbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:signpost-2" /></template>
