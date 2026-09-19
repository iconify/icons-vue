<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pac9bobgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="pac9bobgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:tablet-alt" /></template>
