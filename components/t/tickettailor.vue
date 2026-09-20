<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_fx051-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_fx051-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:tickettailor" /></template>
