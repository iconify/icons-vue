<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-2z779fb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-2z779fb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vase-fill" /></template>
