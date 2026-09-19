<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8nmfubyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8nmfubyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:zones-areas-second-floor" /></template>
