<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvwuj2bty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvwuj2bty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:plane-off" /></template>
