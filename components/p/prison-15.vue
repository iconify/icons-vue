<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frw75db4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="frw75db4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:prison-15" /></template>
