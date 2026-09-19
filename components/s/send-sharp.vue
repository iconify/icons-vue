<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmmn3abfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gmmn3abfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:send-sharp" /></template>
