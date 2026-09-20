<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emnj4mg-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="emnj4mg-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:more-filled" /></template>
