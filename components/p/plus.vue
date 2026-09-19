<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw9ki5i3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="bw9ki5i3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:plus" /></template>
