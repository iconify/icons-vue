<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia_n5zeau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ia_n5zeau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:medusa-light" /></template>
