<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3kfhlbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h3kfhlbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tillywork" /></template>
