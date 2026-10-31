<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcu2-ibcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcu2-ibcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-bag-alt-fill-round" /></template>
