<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye3f1bcxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ye3f1bcxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:maximize" /></template>
