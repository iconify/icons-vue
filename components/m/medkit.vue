<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vog_o-bkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vog_o-bkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:medkit" /></template>
