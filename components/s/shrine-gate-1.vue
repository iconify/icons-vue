<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f92rntbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f92rntbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:shrine-gate-1" /></template>
