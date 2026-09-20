<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcbh3cclu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcbh3cclu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:text" /></template>
