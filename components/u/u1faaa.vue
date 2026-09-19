<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6dzzievb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="l6dzzievb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:u1faaa" /></template>
