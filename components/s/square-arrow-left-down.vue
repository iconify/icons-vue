<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzmj9hbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yzmj9hbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-arrow-left-down" /></template>
