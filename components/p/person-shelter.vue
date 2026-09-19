<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w09pfms2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w09pfms2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:person-shelter" /></template>
