<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpl0je8ew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hpl0je8ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:wifi-alert-attention-bold" /></template>
