<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llsy4sbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llsy4sbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:map-alt-filled" /></template>
