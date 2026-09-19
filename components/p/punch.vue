<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxu40qbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxu40qbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:punch" /></template>
