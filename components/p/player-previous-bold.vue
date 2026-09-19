<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnvii-tja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnvii-tja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:player-previous-bold" /></template>
