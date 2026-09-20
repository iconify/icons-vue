<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phs4js9lq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phs4js9lq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:underline" /></template>
