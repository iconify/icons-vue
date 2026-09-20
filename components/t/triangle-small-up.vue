<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi1ur8_xp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zi1ur8_xp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:triangle-small-up" /></template>
