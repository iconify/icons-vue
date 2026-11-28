<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx3y4h7cs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx3y4h7cs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:zoom-in" /></template>
