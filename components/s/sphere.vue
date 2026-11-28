<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn1h1w93x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rn1h1w93x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:sphere" /></template>
