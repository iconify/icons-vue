<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9qz21bzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":471,"height":1000};
const content = `<path class="c9qz21bzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:up-micro" /></template>
