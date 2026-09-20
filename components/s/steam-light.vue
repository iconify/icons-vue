<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7zbigbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j7zbigbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:steam-light" /></template>
