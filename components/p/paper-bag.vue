<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdmvnc-gt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdmvnc-gt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:paper-bag" /></template>
