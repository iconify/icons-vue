<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn1pmzfrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="vn1pmzfrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:roadsignright" /></template>
