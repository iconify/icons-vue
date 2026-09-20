<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4e_bczgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4e_bczgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:paint-brush-solid" /></template>
