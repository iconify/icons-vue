<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sskbge4in.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="sskbge4in"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:microsoft" /></template>
