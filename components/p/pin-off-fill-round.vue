<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5k55sb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5k55sb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pin-off-fill-round" /></template>
