<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwz5anb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vwz5anb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:resolving" /></template>
