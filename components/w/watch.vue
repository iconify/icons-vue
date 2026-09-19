<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae_zx42gh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ae_zx42gh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:watch" /></template>
