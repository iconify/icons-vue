<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dizbjrbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dizbjrbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:volvo-alt" /></template>
