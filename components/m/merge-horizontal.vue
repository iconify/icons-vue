<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lidfcs8vv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lidfcs8vv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:merge-horizontal" /></template>
