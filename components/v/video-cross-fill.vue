<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dij93bcdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dij93bcdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:video-cross-fill" /></template>
