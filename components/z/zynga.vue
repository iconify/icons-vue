<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dobfjlbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":488};
const content = `<path class="dobfjlbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:zynga" /></template>
