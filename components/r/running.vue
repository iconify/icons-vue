<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu2o_0bsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zu2o_0bsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:running" /></template>
