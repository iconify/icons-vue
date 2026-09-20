<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj2za5ydl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oj2za5ydl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:racket-solid" /></template>
