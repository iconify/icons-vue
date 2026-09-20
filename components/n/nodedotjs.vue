<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do7ha-bts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="do7ha-bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:nodedotjs" /></template>
