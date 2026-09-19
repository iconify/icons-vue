<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzv8w_bxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzv8w_bxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:snes" /></template>
