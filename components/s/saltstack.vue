<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8cl6ubas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":500,"height":512};
const content = `<path class="h8cl6ubas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:saltstack" /></template>
