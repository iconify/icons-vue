<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywe5bx4-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywe5bx4-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:subdirectory-right" /></template>
