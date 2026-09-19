<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8vp_0ldf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="h8vp_0ldf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:portrait" /></template>
