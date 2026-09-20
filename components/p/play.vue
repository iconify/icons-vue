<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg4rwbchc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="xg4rwbchc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:play" /></template>
