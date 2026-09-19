<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8_4hz9uy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8_4hz9uy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:roomsrecreation" /></template>
