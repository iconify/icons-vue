<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2t55rbji.css';
import '../../css/n/nxq0bqbft.css';
import '../../css/d/d99hl0bou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2t55rbji"/><path class="nxq0bqbft"/><path class="d99hl0bou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:phone-calling-bold" /></template>
