<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn3oon7iq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sn3oon7iq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:thunder" /></template>
