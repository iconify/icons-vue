<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szq270g6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szq270g6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:mammotion-luba-top" /></template>
