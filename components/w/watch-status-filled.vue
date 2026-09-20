<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2uf-660j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2uf-660j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:watch-status-filled" /></template>
