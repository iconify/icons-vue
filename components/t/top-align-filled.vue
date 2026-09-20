<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlj-17bjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dlj-17bjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:top-align-filled" /></template>
