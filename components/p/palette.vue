<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6j-pwior.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t6j-pwior"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:palette" /></template>
