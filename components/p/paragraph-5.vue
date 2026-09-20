<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wduv1absz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wduv1absz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:paragraph-5" /></template>
