<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v96dn9r4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v96dn9r4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:music-clef-bass" /></template>
