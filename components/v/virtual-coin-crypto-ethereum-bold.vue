<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-f93z-og.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-f93z-og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:virtual-coin-crypto-ethereum-bold" /></template>
