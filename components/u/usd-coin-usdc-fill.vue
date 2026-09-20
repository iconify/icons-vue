<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rws-_wbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rws-_wbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:usd-coin-usdc-fill" /></template>
