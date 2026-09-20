<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf6utcc_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gf6utcc_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:window-section" /></template>
