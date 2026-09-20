<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jle5wnflo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="jle5wnflo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:police-jp-11" /></template>
