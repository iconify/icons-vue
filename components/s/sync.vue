<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlcegacoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":667};
const content = `<path class="dlcegacoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:sync" /></template>
