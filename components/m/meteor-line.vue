<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eebw1zmin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eebw1zmin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:meteor-line" /></template>
