<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkgeb_bvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bkgeb_bvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:powerpoint" /></template>
