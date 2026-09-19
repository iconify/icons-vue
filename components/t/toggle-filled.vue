<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orjn0-yiw.css';
import '../../css/j/jir5wfbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="orjn0-yiw"/><path class="jir5wfbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:toggle-filled" /></template>
