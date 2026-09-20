<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hl1kp80tz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hl1kp80tz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:onyx-light" /></template>
