<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qagje-7km.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qagje-7km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nintendo-dark" /></template>
