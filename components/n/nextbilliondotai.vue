<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svkx5-wgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svkx5-wgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nextbilliondotai" /></template>
