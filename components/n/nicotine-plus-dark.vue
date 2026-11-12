<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1fuo1lvj.css';
import '../../css/s/sj_lllbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l1fuo1lvj"/><path class="sj_lllbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nicotine-plus-dark" /></template>
