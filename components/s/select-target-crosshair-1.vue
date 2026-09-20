<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs9ntgcgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bs9ntgcgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:select-target-crosshair-1" /></template>
