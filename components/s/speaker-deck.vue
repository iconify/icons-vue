<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7x_debjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7x_debjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:speaker-deck" /></template>
