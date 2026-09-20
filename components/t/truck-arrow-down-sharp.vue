<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk1z-bb0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fk1z-bb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:truck-arrow-down-sharp" /></template>
