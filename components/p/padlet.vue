<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rllhgpk_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rllhgpk_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:padlet" /></template>
