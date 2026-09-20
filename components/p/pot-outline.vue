<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgfyyb3cr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgfyyb3cr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pot-outline" /></template>
