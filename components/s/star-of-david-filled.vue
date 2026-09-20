<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf6tcylxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jf6tcylxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:star-of-david-filled" /></template>
