<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrqdkfz6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nrqdkfz6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:wallet-purse-remix" /></template>
