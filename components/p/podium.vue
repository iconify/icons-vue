<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp0k_5yna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gp0k_5yna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:podium" /></template>
