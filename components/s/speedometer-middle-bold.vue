<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq84j_byz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hq84j_byz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:speedometer-middle-bold" /></template>
