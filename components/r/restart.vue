<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y26g7bcbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y26g7bcbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:restart" /></template>
