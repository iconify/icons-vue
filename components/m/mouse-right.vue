<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl0lw_beo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl0lw_beo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mouse-right" /></template>
