<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4ic-hblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary q4ic-hblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:zodiac-virgo-duotone" /></template>
