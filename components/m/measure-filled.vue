<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e59lt6b9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e59lt6b9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:measure-filled" /></template>
