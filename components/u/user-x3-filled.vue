<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flstyib1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flstyib1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-x3-filled" /></template>
