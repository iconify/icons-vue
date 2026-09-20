<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmdyu-bkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmdyu-bkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:rumble" /></template>
