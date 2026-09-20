<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs8hqxbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fs8hqxbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:triangle-down-filled" /></template>
