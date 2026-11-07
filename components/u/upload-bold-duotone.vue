<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c26kd0bsp.css';
import '../../css/z/zebewq1gn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c26kd0bsp"/><path clip-rule="evenodd" class="zebewq1gn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:upload-bold-duotone" /></template>
