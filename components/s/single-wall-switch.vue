<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul-k7rb9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ul-k7rb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:single-wall-switch" /></template>
