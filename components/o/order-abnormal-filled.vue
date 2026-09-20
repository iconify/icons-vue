<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a20-u-bva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a20-u-bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:order-abnormal-filled" /></template>
