<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb7zws25x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xb7zws25x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:well-pump-powered" /></template>
