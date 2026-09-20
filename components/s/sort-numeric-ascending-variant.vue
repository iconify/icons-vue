<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp2ge7b-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dp2ge7b-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sort-numeric-ascending-variant" /></template>
