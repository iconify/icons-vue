<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hoecnwbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hoecnwbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:pull-request" /></template>
