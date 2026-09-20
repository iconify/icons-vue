<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-j79umnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c-j79umnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:telescope-fill-16" /></template>
