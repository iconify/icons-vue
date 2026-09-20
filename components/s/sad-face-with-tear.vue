<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfyt19vyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bfyt19vyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sad-face-with-tear" /></template>
