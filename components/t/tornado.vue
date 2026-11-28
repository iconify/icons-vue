<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m72nq6vxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m72nq6vxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:tornado" /></template>
