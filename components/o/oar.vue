<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v59gcrb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v59gcrb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:oar" /></template>
