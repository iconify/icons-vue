<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x34ym-b1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x34ym-b1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:paperclip-x" /></template>
