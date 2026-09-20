<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfr_agb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yfr_agb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:map-pin-heart-fill" /></template>
