<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4xlgsbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4xlgsbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:price-tag-line" /></template>
