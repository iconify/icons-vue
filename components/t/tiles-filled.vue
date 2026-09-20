<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rns28kp5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="rns28kp5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:tiles-filled" /></template>
