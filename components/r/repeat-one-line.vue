<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us81xcbgt.css';
import '../../css/w/wpm7l0iir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us81xcbgt"/><path class="wpm7l0iir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:repeat-one-line" /></template>
