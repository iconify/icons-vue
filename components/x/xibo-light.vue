<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/his-o6bcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="his-o6bcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:xibo-light" /></template>
