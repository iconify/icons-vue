<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzrf_m8nb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzrf_m8nb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:new-window" /></template>
