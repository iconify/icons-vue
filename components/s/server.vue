<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otvwr3bnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="otvwr3bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:server" /></template>
