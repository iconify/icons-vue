<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwih3-_ho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="uwih3-_ho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:screen-alt" /></template>
