<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3xvq867s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="o3xvq867s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:vihara" /></template>
