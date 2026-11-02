<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo-tc_4nq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xo-tc_4nq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:taurus-line" /></template>
