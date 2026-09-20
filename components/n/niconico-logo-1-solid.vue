<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sncsgpbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sncsgpbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:niconico-logo-1-solid" /></template>
