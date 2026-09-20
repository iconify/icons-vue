<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_ta-abky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e_ta-abky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:qnap-light" /></template>
