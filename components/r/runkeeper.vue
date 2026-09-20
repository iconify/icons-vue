<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flnsk_y9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flnsk_y9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:runkeeper" /></template>
