<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unxhts-yz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unxhts-yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:wallet-line" /></template>
