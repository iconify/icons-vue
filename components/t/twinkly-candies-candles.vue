<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc85nlbkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xc85nlbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:twinkly-candies-candles" /></template>
