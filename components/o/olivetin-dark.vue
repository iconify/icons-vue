<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj84wmbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bj84wmbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:olivetin-dark" /></template>
