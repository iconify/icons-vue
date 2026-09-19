<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzqmf1b_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzqmf1b_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ungroup" /></template>
