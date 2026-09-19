<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpjm6jbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":23,"height":24};
const content = `<path class="xpjm6jbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:step-forward" /></template>
