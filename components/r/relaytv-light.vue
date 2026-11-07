<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unodwm65o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="unodwm65o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:relaytv-light" /></template>
