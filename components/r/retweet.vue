<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvp9dbb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":640};
const content = `<path class="vvp9dbb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:retweet" /></template>
