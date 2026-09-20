<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2-y6acjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2-y6acjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:transfer-right" /></template>
