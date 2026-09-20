<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txgppvbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txgppvbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:party-balloon-bold" /></template>
