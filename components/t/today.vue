<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx2lb6epn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="bx2lb6epn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:today" /></template>
