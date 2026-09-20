<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkys025md.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pkys025md"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wrench" /></template>
