<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v442e_4zy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v442e_4zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nanoleaf-bulb" /></template>
