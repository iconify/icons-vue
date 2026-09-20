<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs00j1q9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hs00j1q9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timer-add" /></template>
