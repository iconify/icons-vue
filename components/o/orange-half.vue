<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9x9hp0ln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9x9hp0ln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:orange-half" /></template>
