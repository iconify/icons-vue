<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrh1fac9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrh1fac9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:rewind" /></template>
