<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxx8ae6fm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vxx8ae6fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-subway" /></template>
