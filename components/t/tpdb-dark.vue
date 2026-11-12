<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isf22b0cc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="isf22b0cc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tpdb-dark" /></template>
