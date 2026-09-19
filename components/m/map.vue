<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dezeb_bbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dezeb_bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:map" /></template>
