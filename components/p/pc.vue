<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn9-vhbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":328,"height":512};
const content = `<path class="fn9-vhbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:pc" /></template>
