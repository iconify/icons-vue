<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp5-fccdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mp5-fccdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ruler-pen2" /></template>
