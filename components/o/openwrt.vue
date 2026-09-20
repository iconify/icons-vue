<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/feujp6_ax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="feujp6_ax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:openwrt" /></template>
