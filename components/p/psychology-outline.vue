<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tedvp2apz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tedvp2apz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:psychology-outline" /></template>
