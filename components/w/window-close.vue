<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3bzaqblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u3bzaqblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:window-close" /></template>
