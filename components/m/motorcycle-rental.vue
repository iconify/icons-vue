<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xobd5gbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xobd5gbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:motorcycle-rental" /></template>
