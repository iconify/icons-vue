<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgo1esxop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rgo1esxop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:phone" /></template>
