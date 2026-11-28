<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvaosqbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvaosqbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:vase-solid" /></template>
