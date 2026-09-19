<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-cf82kwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":896};
const content = `<path class="s-cf82kwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:miniwink" /></template>
