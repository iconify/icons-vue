<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y74gqacjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y74gqacjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:swipe-left-05" /></template>
