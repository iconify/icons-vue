<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x83uzubhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x83uzubhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:smiling-face-with-eyeglasses" /></template>
