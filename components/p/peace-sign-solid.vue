<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmt8y0odu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmt8y0odu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:peace-sign-solid" /></template>
