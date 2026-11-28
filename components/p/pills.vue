<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcspu-bnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcspu-bnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:pills" /></template>
