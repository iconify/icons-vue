<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y33xhl3hv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y33xhl3hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:panoramic-screen-remix" /></template>
