<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkshjbcxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mkshjbcxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:welcome-comments" /></template>
