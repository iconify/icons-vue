<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuu8dbcmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fuu8dbcmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:move" /></template>
