<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6e0rsfdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6e0rsfdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:roblox" /></template>
