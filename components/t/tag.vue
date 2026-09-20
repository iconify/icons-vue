<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn4a4d53k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="sn4a4d53k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:tag" /></template>
