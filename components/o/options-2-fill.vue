<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2ca7acla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2ca7acla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:options-2-fill" /></template>
