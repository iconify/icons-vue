<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m78x-1hxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m78x-1hxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:trash" /></template>
