<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iiwrv8p2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iiwrv8p2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:move-down-1-bold" /></template>
