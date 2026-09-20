<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icuogwm2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icuogwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:map-check" /></template>
