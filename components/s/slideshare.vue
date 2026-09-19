<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5balybot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r5balybot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:slideshare" /></template>
