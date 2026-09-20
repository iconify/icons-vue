<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-6d4u1ph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="n-6d4u1ph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:overtime-filled" /></template>
