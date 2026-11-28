<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f72s_7ovt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f72s_7ovt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sunset-solid" /></template>
