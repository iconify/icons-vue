<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5_1oqbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5_1oqbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:rooms-other" /></template>
