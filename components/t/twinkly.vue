<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-075ccvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-075ccvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:twinkly" /></template>
