<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myzwccaqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":640};
const content = `<path class="myzwccaqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:videocamerathree" /></template>
