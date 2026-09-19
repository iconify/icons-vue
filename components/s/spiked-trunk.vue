<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1gj65euc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t1gj65euc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spiked-trunk" /></template>
