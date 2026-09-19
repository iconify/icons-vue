<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-zxp2bdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="h-zxp2bdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:person" /></template>
