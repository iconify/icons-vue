<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmvew9bpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gmvew9bpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nike-light" /></template>
