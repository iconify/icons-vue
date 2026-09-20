<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlg3n8bgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vlg3n8bgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:rhomb-filled" /></template>
