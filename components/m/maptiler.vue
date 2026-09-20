<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd6pvxbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd6pvxbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:maptiler" /></template>
