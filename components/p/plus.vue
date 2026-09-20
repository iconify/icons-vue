<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x296-cbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x296-cbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:plus" /></template>
