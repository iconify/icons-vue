<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcje6dbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcje6dbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:stamp" /></template>
