<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0_jigb-j.css';
import '../../css/x/xjr5jrboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0_jigb-j"/><path class="xjr5jrboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:radio" /></template>
