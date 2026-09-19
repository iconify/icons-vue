<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su07ufx8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="su07ufx8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-medical" /></template>
