<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-h-_ubmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g-h-_ubmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:wifi-abnormal-filled" /></template>
