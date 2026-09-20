<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c796d29xi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c796d29xi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:shop-sale-1" /></template>
