<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlbf1yb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlbf1yb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:payload-cms" /></template>
