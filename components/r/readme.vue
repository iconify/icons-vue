<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdvfmbbbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wdvfmbbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:readme" /></template>
