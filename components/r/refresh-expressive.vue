<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_6214s-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_6214s-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:refresh-expressive" /></template>
