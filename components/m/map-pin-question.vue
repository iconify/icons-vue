<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi3txqbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zi3txqbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:map-pin-question" /></template>
