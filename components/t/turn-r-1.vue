<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc15skb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc15skb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:turn-r-1" /></template>
