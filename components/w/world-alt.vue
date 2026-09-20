<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj2ntd1ke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="pj2ntd1ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:world-alt" /></template>
