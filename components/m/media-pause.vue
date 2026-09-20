<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9czsj7qk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="n9czsj7qk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:media-pause" /></template>
