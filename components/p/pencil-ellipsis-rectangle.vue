<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5940d3ll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="b5940d3ll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:pencil-ellipsis-rectangle" /></template>
