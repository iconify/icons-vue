<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cozlh9whk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cozlh9whk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:paint" /></template>
