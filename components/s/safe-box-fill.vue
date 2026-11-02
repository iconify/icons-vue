<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dir-0qbkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dir-0qbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:safe-box-fill" /></template>
