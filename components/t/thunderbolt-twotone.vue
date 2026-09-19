<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi-0u1b-k.css';
import '../../css/f/fdsk41g4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fi-0u1b-k"/><path class="fdsk41g4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:thunderbolt-twotone" /></template>
