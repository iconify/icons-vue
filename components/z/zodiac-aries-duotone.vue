<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2pz2ibnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary v2pz2ibnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:zodiac-aries-duotone" /></template>
