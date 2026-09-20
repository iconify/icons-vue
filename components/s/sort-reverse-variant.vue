<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhqwdhnkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhqwdhnkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sort-reverse-variant" /></template>
