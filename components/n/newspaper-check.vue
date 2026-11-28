<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lllxgebsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lllxgebsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:newspaper-check" /></template>
