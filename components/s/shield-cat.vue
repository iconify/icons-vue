<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl-8y1hvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tl-8y1hvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:shield-cat" /></template>
