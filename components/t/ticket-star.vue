<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn1isfbbx.css';
import '../../css/d/d_e6qbb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zn1isfbbx"/><path class="d_e6qbb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:ticket-star" /></template>
