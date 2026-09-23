<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubpmymb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubpmymb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:radical-two-tone" /></template>
