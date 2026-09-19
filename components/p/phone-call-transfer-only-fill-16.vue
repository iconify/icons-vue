<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psvt2kbpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="psvt2kbpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-call-transfer-only-fill-16" /></template>
