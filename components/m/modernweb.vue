<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn5e1o2rf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wn5e1o2rf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:modernweb" /></template>
