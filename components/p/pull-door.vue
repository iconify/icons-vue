<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obua1kb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="obua1kb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:pull-door" /></template>
