<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlzd_xg5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="jlzd_xg5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:music-equalizer" /></template>
