<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wod1mxbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wod1mxbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:stop-circle-solid" /></template>
