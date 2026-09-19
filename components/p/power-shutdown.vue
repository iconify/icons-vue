<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mav55wb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mav55wb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:power-shutdown" /></template>
