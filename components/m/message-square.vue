<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cssc3wurj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cssc3wurj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:message-square" /></template>
