<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uiyq-lezc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="uiyq-lezc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:sledding" /></template>
