<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx8-v0blk.css';
import '../../css/a/amiveibiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bx8-v0blk"/><path clip-rule="evenodd" class="amiveibiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:run-16" /></template>
