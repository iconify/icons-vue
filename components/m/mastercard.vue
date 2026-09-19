<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w52e9yb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="w52e9yb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:mastercard" /></template>
