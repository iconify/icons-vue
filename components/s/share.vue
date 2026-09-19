<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r10aijb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="r10aijb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:share" /></template>
