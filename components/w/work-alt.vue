<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx7oz3bbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rx7oz3bbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:work-alt" /></template>
