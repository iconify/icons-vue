<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d08ip4b7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d08ip4b7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:network-check" /></template>
