<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0p2aabxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0p2aabxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:moon3-filled" /></template>
