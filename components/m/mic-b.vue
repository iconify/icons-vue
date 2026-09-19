<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6-4xurgn.css';
import '../../css/a/am0up7b7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j6-4xurgn"/><path class="am0up7b7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:mic-b" /></template>
