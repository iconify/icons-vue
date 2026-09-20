<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1c76acum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m1c76acum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:stoat-light" /></template>
