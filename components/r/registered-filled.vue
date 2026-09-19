<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy03h6b4p.css';
import '../../css/b/bqc5p2b1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy03h6b4p"/><path class="bqc5p2b1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:registered-filled" /></template>
