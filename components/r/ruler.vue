<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/terlyubqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="terlyubqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:ruler" /></template>
