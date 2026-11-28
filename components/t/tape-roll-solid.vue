<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzzlidw_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzzlidw_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tape-roll-solid" /></template>
