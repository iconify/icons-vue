<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogg2qpwxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogg2qpwxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:truck-solid" /></template>
