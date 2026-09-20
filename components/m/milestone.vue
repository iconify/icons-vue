<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_4c0j6gx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c_4c0j6gx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:milestone" /></template>
