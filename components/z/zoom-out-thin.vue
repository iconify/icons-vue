<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_01jj14b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_01jj14b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:zoom-out-thin" /></template>
