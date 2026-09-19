<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rixak_2_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rixak_2_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:phone-outcome-solid" /></template>
