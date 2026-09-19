<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nts4n-9sa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nts4n-9sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:player-next-bold" /></template>
