<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-1-tpf5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y-1-tpf5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-point-search-bold" /></template>
