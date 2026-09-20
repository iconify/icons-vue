<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st9o-6h2k.css';
import '../../css/l/lgnrw_bhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="st9o-6h2k"/><path class="lgnrw_bhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:up-down-black-arrow" /></template>
