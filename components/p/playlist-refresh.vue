<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzv-gcbon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzv-gcbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:playlist-refresh" /></template>
