<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlyetv7ls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vlyetv7ls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-word-2018-light" /></template>
