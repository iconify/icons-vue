<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi1q-lbdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi1q-lbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:smart-home-gear" /></template>
