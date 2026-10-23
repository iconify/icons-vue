<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrhfs_jsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrhfs_jsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:save" /></template>
