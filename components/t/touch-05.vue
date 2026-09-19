<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0-d_4-vv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0-d_4-vv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:touch-05" /></template>
