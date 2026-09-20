<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-rvsvb_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-rvsvb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:maps-bold" /></template>
