<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfhg5ym_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfhg5ym_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:touch" /></template>
