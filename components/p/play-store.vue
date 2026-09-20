<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa63bdbwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="qa63bdbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:play-store" /></template>
