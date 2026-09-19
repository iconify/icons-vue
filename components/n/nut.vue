<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqhhrj0le.css';
import '../../css/g/gt9eulz_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqhhrj0le"/><path class="gt9eulz_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:nut" /></template>
