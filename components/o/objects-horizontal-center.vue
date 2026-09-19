<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jib_m7btj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jib_m7btj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:objects-horizontal-center" /></template>
