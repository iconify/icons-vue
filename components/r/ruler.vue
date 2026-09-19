<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp02d1q5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp02d1q5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:ruler" /></template>
