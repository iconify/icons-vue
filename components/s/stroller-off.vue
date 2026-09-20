<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh6iiv50u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hh6iiv50u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:stroller-off" /></template>
