<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5wunscny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y5wunscny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:route-target" /></template>
