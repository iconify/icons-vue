<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vho_s5bgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vho_s5bgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:share-location-hand-bold" /></template>
