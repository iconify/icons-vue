<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvfubbcro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvfubbcro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:skypeforbusiness" /></template>
