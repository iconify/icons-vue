<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuxo34wrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fuxo34wrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:style-two-pin-home-bold" /></template>
