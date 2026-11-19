<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvy27v4ee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fvy27v4ee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:telltaledns-dark" /></template>
