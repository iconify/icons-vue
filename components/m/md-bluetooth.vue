<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-gg5db1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t-gg5db1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-bluetooth" /></template>
