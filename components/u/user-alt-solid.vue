<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp2x7ac1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lp2x7ac1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:user-alt-solid" /></template>
