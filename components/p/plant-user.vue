<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vli6zsotx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vli6zsotx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:plant-user" /></template>
