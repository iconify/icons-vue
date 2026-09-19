<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/b7t_h5btd.css';
import '../../css/n/nft7dqf3o.css';
import '../../css/q/qeazwhzjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b7t_h5btd"/><path class="nft7dqf3o"/><path class="qeazwhzjd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:money-receive-square" /></template>
