<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouc14g95t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ouc14g95t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:spellcheck" /></template>
