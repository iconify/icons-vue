<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw4t0zb6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yw4t0zb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:phone-pen-2-solid" /></template>
