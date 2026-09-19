<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op1eu4bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op1eu4bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:medal-alt" /></template>
