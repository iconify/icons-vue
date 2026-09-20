<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5ckzvuqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y5ckzvuqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:trumpet-16" /></template>
