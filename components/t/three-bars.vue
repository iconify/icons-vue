<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyf10rbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":16};
const content = `<path class="vyf10rbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:three-bars" /></template>
