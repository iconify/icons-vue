<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asf4shgzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="asf4shgzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:snowboarding" /></template>
