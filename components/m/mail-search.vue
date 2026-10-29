<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb05kotbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb05kotbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:mail-search" /></template>
