<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tph2u6z3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tph2u6z3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:robot-vacuum-pause" /></template>
