<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn0_anb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fn0_anb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:skip-minus" /></template>
