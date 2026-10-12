<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz_m0fb4u.css';
import '../../css/y/yuu2iyljg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dz_m0fb4u"/><path clip-rule="evenodd" class="yuu2iyljg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ratio-filled" /></template>
