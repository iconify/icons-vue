<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9gdvs6ko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="a9gdvs6ko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:view-expand" /></template>
