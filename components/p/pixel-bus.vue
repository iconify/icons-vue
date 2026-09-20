<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0zuo8b6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="a0zuo8b6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-bus" /></template>
