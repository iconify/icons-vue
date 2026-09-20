<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyj6-4hbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="xyj6-4hbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:receive" /></template>
