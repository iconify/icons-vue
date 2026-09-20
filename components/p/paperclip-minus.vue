<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx1s_bbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx1s_bbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:paperclip-minus" /></template>
