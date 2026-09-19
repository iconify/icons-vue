<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adci3faeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="adci3faeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:star-half" /></template>
