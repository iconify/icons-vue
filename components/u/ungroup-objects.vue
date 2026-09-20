<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj8h-z_we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dj8h-z_we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:ungroup-objects" /></template>
