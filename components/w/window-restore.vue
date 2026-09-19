<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-xd5diqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h-xd5diqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:window-restore" /></template>
