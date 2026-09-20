<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4e-psbwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4e-psbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:podium-gold" /></template>
