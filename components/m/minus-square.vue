<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/peafspbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="peafspbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:minus-square" /></template>
