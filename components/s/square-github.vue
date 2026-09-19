<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xye8dcczv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="xye8dcczv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:square-github" /></template>
