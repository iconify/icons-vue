<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i13rn9bvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="i13rn9bvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:sdvideo" /></template>
