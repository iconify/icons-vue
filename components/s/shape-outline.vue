<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zssm3ybnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zssm3ybnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shape-outline" /></template>
