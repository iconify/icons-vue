<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdbh8k3zh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vdbh8k3zh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:peanut-dark" /></template>
