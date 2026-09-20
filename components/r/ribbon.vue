<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nakn7tj0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nakn7tj0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ribbon" /></template>
