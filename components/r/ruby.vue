<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_9_kub0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_9_kub0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:ruby" /></template>
