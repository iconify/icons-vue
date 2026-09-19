<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylte6_80y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ylte6_80y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:pencil-alt" /></template>
