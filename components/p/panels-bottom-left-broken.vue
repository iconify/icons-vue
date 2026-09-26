<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/tcg0b8fzd.css';
import '../../css/s/sma0a9bhx.css';
import '../../css/k/k-xqiwbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tcg0b8fzd"/><path class="sma0a9bhx"/><path class="k-xqiwbqo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panels-bottom-left-broken" /></template>
