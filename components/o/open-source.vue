<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dku49ip6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dku49ip6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:open-source" /></template>
