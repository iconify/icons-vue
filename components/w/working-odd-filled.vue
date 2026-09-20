<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iff-1kjzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="iff-1kjzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:working-odd-filled" /></template>
