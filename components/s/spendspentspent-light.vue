<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxuqicpwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mxuqicpwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:spendspentspent-light" /></template>
