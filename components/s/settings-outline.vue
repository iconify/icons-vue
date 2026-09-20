<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgqr2umbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgqr2umbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:settings-outline" /></template>
