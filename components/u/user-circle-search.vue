<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p285etblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p285etblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:user-circle-search" /></template>
