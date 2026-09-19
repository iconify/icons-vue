<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc98sqlxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wc98sqlxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:zodiac-libra" /></template>
