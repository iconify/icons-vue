<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfyk-ub-n.css';
import '../../css/h/hbzul7b_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="xfyk-ub-n"/><path class="hbzul7b_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:rewind-ten" /></template>
