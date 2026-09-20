<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvb64fcio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvb64fcio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:opera" /></template>
