<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqdj_sbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="gqdj_sbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:truck-field-un" /></template>
