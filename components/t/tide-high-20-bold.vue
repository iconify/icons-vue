<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_3o7hbpq.css';
import '../../css/q/qfoc8pfkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t_3o7hbpq"/><path class="qfoc8pfkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tide-high-20-bold" /></template>
