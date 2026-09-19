<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp_uagnzf.css';
import '../../css/z/zwr_uxclv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zp_uagnzf"/><path class="zwr_uxclv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:piggy-bank" /></template>
