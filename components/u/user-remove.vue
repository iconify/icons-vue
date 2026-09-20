<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbnj8bycg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbnj8bycg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:user-remove" /></template>
