<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gae6d5d6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gae6d5d6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:vector-16" /></template>
