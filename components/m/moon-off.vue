<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pab-3wh6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pab-3wh6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:moon-off" /></template>
