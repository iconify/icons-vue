<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls14v99op.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ls14v99op"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:paperclip-plus" /></template>
