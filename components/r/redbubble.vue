<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l93bvgtdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l93bvgtdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:redbubble" /></template>
