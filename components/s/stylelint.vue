<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-sr4yt-t.css';
import '../../css/l/l3cxynbly.css';
import '../../css/a/asc15gb8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":525,"height":512};
const content = `<path class="z-sr4yt-t"/><path class="l3cxynbly"/><path class="asc15gb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:stylelint" /></template>
