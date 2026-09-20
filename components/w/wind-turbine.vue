<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3lc6z75g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3lc6z75g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wind-turbine" /></template>
