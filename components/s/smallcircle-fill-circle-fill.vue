<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6w734d5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="f6w734d5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:smallcircle-fill-circle-fill" /></template>
