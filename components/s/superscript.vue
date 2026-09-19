<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr5psgb2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hr5psgb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:superscript" /></template>
