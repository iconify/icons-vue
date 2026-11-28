<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xldl5kbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xldl5kbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:picture-in-picture-solid" /></template>
