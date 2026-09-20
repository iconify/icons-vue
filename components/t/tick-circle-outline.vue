<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-gf19h6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-gf19h6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tick-circle-outline" /></template>
