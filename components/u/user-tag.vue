<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-x1pobvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="z-x1pobvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:user-tag" /></template>
