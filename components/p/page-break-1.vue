<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7to8vrmi.css';
import '../../css/r/r49wnackk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="a7to8vrmi"/><path class="r49wnackk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:page-break-1" /></template>
