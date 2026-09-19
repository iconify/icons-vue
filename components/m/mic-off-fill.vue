<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6z7a8-0d.css';
import '../../css/k/kebsqacsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6z7a8-0d"/><path class="kebsqacsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:mic-off-fill" /></template>
