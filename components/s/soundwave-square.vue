<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is8se_vww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="is8se_vww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:soundwave-square" /></template>
