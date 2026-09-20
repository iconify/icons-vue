<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp2pmeb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="pp2pmeb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:reply" /></template>
