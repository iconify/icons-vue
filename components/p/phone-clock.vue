<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eik6_sx3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eik6_sx3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:phone-clock" /></template>
