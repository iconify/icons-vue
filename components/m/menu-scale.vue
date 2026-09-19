<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7ru8cc_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7ru8cc_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:menu-scale" /></template>
