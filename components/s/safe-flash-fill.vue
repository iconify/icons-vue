<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdo9_1h6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdo9_1h6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:safe-flash-fill" /></template>
