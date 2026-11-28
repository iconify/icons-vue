<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhu-10bri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhu-10bri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pound-sterling-solid" /></template>
