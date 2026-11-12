<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njq8_c_rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="njq8_c_rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:notifiarr-dark" /></template>
