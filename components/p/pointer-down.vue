<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8h8dllmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="b8h8dllmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:pointer-down" /></template>
