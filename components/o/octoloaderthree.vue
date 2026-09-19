<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxi-l1bjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lxi-l1bjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:octoloaderthree" /></template>
