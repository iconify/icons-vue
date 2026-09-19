<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moidvm7mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="moidvm7mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:settings-outline" /></template>
