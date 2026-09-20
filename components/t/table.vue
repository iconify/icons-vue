<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyw4_cb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wyw4_cb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:table" /></template>
