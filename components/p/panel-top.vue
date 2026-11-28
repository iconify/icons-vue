<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp3wfw2-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sp3wfw2-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:panel-top" /></template>
