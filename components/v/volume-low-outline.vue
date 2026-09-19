<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsh4_td-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gsh4_td-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:volume-low-outline" /></template>
