<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1abfbc-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="i1abfbc-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:time-countdown" /></template>
