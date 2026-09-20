<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu0jkqbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu0jkqbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mouse-move-up" /></template>
