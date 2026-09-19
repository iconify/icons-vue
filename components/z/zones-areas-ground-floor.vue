<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_o_yvwyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_o_yvwyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:zones-areas-ground-floor" /></template>
