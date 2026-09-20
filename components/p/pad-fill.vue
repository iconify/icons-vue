<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs4rpkbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qs4rpkbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pad-fill" /></template>
