<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0cz78sbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r0cz78sbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:ripple" /></template>
