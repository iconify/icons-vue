<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3y7vob_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="q3y7vob_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:twitter-square" /></template>
