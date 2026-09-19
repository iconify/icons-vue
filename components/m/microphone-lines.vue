<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9w3olbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="c9w3olbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:microphone-lines" /></template>
