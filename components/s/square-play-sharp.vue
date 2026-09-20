<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg3pwub2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dg3pwub2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-play-sharp" /></template>
