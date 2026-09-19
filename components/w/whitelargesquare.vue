<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gln9e_ezj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gln9e_ezj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:whitelargesquare" /></template>
