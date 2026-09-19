<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsnbt6b8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="lsnbt6b8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:ruler-horizontal" /></template>
