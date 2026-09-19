<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_3_bibbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_3_bibbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:player-previous-thin" /></template>
