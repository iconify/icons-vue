<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/y4ufzepjc.css';
import '../../css/n/nftqa09ol.css';
import '../../css/b/bsyh3b5uz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="y4ufzepjc"/><path class="nftqa09ol"/><path class="bsyh3b5uz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:message-dots-round-download" /></template>
