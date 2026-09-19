<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3q7pac3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3q7pac3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:swipe-two-fingers-left-gesture" /></template>
