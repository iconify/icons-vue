<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldc4q4jfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldc4q4jfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:upload-alt" /></template>
