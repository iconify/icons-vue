<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g43n1dbsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":448};
const content = `<path class="g43n1dbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:truck-1" /></template>
