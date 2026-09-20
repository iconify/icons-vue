<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hiz9-olbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hiz9-olbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:stumbleupon" /></template>
