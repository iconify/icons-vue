<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn2ue_csy.css';
import '../../css/p/p6thd6bpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="zn2ue_csy"/><path class="p6thd6bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:share" /></template>
