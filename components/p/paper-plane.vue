<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffzimobwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ffzimobwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:paper-plane" /></template>
