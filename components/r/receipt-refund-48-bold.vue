<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk4s-jblr.css';
import '../../css/o/o2ddx5b5f.css';
import '../../css/j/jrnu5tbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qk4s-jblr"/><path class="o2ddx5b5f"/><path class="jrnu5tbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:receipt-refund-48-bold" /></template>
