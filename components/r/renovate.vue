<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyduyab8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyduyab8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:renovate" /></template>
