<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc_d3616n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kc_d3616n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mcdonald-s" /></template>
