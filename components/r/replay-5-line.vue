<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnseq_fuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnseq_fuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:replay-5-line" /></template>
