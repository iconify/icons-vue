<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xupgi1b6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xupgi1b6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:victron-energy" /></template>
