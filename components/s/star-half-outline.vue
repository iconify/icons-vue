<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_jz5xwqo.css';
import '../../css/n/nx8_58b1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x_jz5xwqo"/><path class="nx8_58b1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:star-half-outline" /></template>
