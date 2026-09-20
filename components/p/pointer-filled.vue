<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql8oqjbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ql8oqjbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:pointer-filled" /></template>
