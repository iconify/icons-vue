<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu0__ibun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hu0__ibun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pixelsphere" /></template>
