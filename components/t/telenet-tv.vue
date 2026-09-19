<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgqgi3exg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgqgi3exg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:telenet-tv" /></template>
