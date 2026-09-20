<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhov7xoyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhov7xoyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:verified-badge-fill" /></template>
