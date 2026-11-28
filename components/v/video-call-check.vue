<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mid5d7o1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mid5d7o1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:video-call-check" /></template>
