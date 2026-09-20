<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik-bhfbuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ik-bhfbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:step-backward-alt" /></template>
