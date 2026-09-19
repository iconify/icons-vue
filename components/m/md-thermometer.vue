<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhz84bc7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hhz84bc7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-thermometer" /></template>
