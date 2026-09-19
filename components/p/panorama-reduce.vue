<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpockd_pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpockd_pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:panorama-reduce" /></template>
