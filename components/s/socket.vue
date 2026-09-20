<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2h16x32u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2h16x32u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:socket" /></template>
