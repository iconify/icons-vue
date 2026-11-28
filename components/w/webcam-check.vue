<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t440isbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t440isbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:webcam-check" /></template>
