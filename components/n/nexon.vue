<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc1a-qb_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qc1a-qb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:nexon" /></template>
