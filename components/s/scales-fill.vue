<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfdxn2bwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfdxn2bwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:scales-fill" /></template>
