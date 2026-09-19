<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcje_ok-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcje_ok-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:trade-mark-circle" /></template>
