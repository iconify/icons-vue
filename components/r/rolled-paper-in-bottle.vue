<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avn891jjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="avn891jjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:rolled-paper-in-bottle" /></template>
