<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7csh6b4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="l7csh6b4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:user" /></template>
