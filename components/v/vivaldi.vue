<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzvcr_bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzvcr_bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:vivaldi" /></template>
