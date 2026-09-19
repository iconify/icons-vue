<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-c76yb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="x-c76yb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:poll" /></template>
