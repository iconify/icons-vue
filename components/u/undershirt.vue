<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyrdlb1pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyrdlb1pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:undershirt" /></template>
