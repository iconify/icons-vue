<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opn9adbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="opn9adbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:white-tower" /></template>
