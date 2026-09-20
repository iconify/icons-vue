<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va893noiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="va893noiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:san-francisco-municipal-railway" /></template>
