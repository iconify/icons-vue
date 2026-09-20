<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlr07wbhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xlr07wbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:shelf-up-filled" /></template>
