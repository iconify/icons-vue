<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf1043y0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="jf1043y0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:school-jp-11" /></template>
