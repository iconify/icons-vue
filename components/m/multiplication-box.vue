<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke7fu1b3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ke7fu1b3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:multiplication-box" /></template>
