<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4rc10b4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="x4rc10b4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:rain" /></template>
