<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmfxnmbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmfxnmbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-more-horizontal-fill-round" /></template>
