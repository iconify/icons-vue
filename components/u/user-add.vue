<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl0smq5gu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vl0smq5gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:user-add" /></template>
